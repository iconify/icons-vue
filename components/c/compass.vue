<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr8-a7llk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="sr8-a7llk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:compass" /></template>
