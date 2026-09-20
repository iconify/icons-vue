<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfudd0blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfudd0blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:itchdotio" /></template>
