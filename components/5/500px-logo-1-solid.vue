<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whx76-5qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whx76-5qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:500px-logo-1-solid" /></template>
