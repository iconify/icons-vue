<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf4sslb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf4sslb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bell-notification-solid" /></template>
