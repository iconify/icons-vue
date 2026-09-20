<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scih79b8c.css';
import '../../css/m/me4-nbcbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scih79b8c"/><path class="me4-nbcbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dcr" /></template>
