<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xey0jwb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xey0jwb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:angular-wordmark" /></template>
