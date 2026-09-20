<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc5kqobel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hc5kqobel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-hangouts-meet-logo-solid" /></template>
