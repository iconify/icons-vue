<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isdg-2boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isdg-2boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:gender-female" /></template>
