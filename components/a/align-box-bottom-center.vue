<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxfw4rbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxfw4rbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-bottom-center" /></template>
