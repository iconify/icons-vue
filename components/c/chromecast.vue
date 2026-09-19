<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfrqolb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kfrqolb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:chromecast" /></template>
