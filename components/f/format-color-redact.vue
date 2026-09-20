<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g973wvayq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g973wvayq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-color-redact" /></template>
