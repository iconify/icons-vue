<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjmqm-lbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjmqm-lbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:car-taxi-front-solid" /></template>
