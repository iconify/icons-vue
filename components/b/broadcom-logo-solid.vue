<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grcmtww9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grcmtww9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:broadcom-logo-solid" /></template>
