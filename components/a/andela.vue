<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhf0-4f-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhf0-4f-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:andela" /></template>
