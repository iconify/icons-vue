<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xap7szbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xap7szbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hedge" /></template>
