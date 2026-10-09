<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wetq5b_1u.css';
import '../../css/y/ysix8mbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wetq5b_1u"/><path class="ysix8mbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-20" /></template>
