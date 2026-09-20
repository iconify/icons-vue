<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncxk4z-et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncxk4z-et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lina" /></template>
