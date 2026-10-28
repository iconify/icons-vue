<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p162yovcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p162yovcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:homey" /></template>
