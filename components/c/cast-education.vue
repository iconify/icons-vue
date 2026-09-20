<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qofpi6brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qofpi6brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cast-education" /></template>
