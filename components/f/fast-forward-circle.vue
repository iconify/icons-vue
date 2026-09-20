<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i37e_xbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="i37e_xbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:fast-forward-circle" /></template>
