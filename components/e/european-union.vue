<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu6-2cbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu6-2cbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:european-union" /></template>
