<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc3whdc8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc3whdc8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:debrid-link" /></template>
