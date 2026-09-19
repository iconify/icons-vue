<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpn_r7b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpn_r7b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dam" /></template>
