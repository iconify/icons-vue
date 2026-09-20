<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds5x1fh_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds5x1fh_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:devexpress" /></template>
