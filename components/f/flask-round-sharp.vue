<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw6mbk9pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw6mbk9pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-round-sharp" /></template>
