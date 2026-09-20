<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov7mw7bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov7mw7bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-hangouts-meet-logo-block" /></template>
