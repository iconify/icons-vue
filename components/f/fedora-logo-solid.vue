<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quu-ipb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="quu-ipb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fedora-logo-solid" /></template>
