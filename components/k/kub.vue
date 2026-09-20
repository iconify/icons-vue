<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky3n2u_io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky3n2u_io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kub" /></template>
