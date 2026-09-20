<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw7la6btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw7la6btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-minus" /></template>
