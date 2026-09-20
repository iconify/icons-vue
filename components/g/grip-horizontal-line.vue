<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpwpxn17c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpwpxn17c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:grip-horizontal-line" /></template>
