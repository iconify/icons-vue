<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwt2_zb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwt2_zb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kodi-logo" /></template>
