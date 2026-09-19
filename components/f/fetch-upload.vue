<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiuwblb7l.css';
import '../../css/z/zy_wagb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wiuwblb7l"/><path class="zy_wagb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fetch-upload" /></template>
