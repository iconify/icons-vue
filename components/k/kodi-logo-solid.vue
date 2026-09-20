<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r954v1bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r954v1bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kodi-logo-solid" /></template>
