<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9uj-ij0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v9uj-ij0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:invisible-2-solid" /></template>
