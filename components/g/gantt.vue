<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3g7w1yyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3g7w1yyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:gantt" /></template>
