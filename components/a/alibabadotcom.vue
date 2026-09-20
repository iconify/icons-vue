<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr8ei8bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr8ei8bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alibabadotcom" /></template>
