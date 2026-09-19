<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jesw7_b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jesw7_b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:beer" /></template>
