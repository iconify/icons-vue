<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf3z-bcyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kf3z-bcyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:checkbox" /></template>
