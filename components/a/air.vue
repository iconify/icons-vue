<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8ad2mbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8ad2mbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:air" /></template>
