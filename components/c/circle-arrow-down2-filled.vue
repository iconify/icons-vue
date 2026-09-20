<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw_sl3b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iw_sl3b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-down2-filled" /></template>
