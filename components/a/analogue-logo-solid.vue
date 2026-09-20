<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udi048kbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udi048kbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:analogue-logo-solid" /></template>
