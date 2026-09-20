<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsp3hvgtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsp3hvgtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lotion" /></template>
