<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofi3dj95o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofi3dj95o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-2-thin" /></template>
