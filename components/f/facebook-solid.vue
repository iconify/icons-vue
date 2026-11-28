<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrp280b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrp280b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:facebook-solid" /></template>
