<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob7kc6bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ob7kc6bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:clock-plus-light" /></template>
