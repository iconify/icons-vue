<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy-4qo5at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy-4qo5at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:gift-2-solid" /></template>
