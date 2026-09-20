<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym7iefm2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym7iefm2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lastfm-logo-solid" /></template>
