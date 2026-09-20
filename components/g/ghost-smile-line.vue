<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfxwozjpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxwozjpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ghost-smile-line" /></template>
