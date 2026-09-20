<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd3qvte3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pd3qvte3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-drive-logo-2-solid" /></template>
