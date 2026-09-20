<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np1ww71-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="np1ww71-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fork-plate-solid" /></template>
