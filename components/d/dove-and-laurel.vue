<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkj27dj0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wkj27dj0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dove-and-laurel" /></template>
