<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdjboku7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tdjboku7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:aws" /></template>
