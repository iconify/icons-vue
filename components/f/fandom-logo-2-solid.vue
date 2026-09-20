<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooonye2mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ooonye2mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fandom-logo-2-solid" /></template>
