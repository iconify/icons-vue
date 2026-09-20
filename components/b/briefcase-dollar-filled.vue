<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxemdwd5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxemdwd5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:briefcase-dollar-filled" /></template>
