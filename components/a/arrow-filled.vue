<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twku4hbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":24};
const content = `<path class="twku4hbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:arrow-filled" /></template>
