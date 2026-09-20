<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phlg5e-oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phlg5e-oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:irc-galleria-logo-solid" /></template>
