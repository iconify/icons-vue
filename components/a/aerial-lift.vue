<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mms7eybus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mms7eybus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:aerial-lift" /></template>
