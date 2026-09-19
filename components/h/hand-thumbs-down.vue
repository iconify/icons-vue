<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-lbbobiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f-lbbobiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hand-thumbs-down" /></template>
