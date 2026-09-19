<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc1rx7bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc1rx7bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-js" /></template>
