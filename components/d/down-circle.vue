<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3umnt9ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3umnt9ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:down-circle" /></template>
