<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m400souyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m400souyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-check-fill" /></template>
