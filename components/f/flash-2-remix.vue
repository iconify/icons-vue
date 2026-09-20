<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1yxcf2mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="v1yxcf2mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flash-2-remix" /></template>
