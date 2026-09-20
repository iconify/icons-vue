<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht47-7b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht47-7b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gentoo" /></template>
