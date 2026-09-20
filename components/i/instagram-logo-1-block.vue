<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diko8da2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="diko8da2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:instagram-logo-1-block" /></template>
