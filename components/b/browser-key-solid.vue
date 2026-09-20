<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr7zo8bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vr7zo8bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-key-solid" /></template>
