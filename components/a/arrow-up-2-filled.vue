<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/std8ps_jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="std8ps_jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-2-filled" /></template>
