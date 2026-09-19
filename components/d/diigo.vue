<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow8pqgbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":264,"height":488};
const content = `<path class="ow8pqgbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:diigo" /></template>
