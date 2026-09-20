<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc61b2bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc61b2bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:arch-linux-logo-solid" /></template>
