<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ct7fbgs.css';
import '../../css/z/z5f1jwb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n9ct7fbgs"/><path class="z5f1jwb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cloud-arrow-down-stroke-20" /></template>
