<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzkmd1-7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzkmd1-7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bravia" /></template>
