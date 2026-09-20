<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mijns_5go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mijns_5go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:align-left-justify" /></template>
