<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3w0o-4uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3w0o-4uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:abletonlive" /></template>
