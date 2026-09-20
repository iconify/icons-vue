<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br0tc3bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br0tc3bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kashflow" /></template>
