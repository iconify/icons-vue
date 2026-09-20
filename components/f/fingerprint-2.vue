<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkclc-bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkclc-bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fingerprint-2" /></template>
