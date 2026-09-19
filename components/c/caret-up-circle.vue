<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7rwn8boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h7rwn8boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:caret-up-circle" /></template>
