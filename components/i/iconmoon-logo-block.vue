<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwp7c3b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwp7c3b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:iconmoon-logo-block" /></template>
