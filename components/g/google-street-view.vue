<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlq2vxlgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlq2vxlgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-street-view" /></template>
