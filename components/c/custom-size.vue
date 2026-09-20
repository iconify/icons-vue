<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv0helbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv0helbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:custom-size" /></template>
