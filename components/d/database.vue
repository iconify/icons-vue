<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-07p3bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-07p3bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:database" /></template>
