<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szmw6ngwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szmw6ngwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:deskphone-filled" /></template>
