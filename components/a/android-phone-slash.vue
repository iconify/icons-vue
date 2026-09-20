<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ihcm2lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-ihcm2lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:android-phone-slash" /></template>
