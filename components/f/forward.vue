<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpuy1fb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="tpuy1fb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:forward" /></template>
