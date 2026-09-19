<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6-_cry7c.css';
import '../../css/m/mhc-lebus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer p6-_cry7c"/><path class="duoicon-secondary-layer mhc-lebus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:lamp" /></template>
