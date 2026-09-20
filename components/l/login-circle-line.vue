<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbsc4s31x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbsc4s31x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:login-circle-line" /></template>
