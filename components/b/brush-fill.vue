<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpdtpug0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpdtpug0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:brush-fill" /></template>
