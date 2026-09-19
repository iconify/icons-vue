<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai7padzmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ai7padzmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flash" /></template>
