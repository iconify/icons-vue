<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qix0zlbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qix0zlbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:junit5" /></template>
