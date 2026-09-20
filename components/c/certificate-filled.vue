<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la79tccyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la79tccyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:certificate-filled" /></template>
