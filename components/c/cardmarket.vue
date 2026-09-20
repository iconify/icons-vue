<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj_nm5bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_nm5bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cardmarket" /></template>
