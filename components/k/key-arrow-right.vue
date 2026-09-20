<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfqcat_ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfqcat_ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:key-arrow-right" /></template>
