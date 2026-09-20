<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqn6k6b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqn6k6b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:clickup" /></template>
