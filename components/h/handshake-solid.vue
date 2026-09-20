<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvq5dx-8z.css';
import '../../css/n/nj-jrfb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvq5dx-8z"/><path class="nj-jrfb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:handshake-solid" /></template>
