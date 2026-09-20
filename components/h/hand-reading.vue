<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgi_vyerr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgi_vyerr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-reading" /></template>
