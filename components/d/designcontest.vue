<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyxrfty-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":1025};
const content = `<path class="yyxrfty-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:designcontest" /></template>
