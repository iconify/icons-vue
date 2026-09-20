<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh4luxbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rh4luxbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:lastpass-logo-solid" /></template>
