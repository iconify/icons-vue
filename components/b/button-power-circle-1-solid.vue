<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcw13cbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcw13cbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:button-power-circle-1-solid" /></template>
