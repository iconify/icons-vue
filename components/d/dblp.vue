<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn9a3fbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn9a3fbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dblp" /></template>
