<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-dvttbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-dvttbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hue-only" /></template>
