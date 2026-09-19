<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zps83bc6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zps83bc6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-kiss" /></template>
