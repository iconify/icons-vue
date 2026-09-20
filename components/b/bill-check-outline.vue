<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vabi4ybbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vabi4ybbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-check-outline" /></template>
