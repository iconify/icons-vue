<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykqcwh8cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ykqcwh8cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:floors" /></template>
