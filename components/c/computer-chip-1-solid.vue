<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngbaxtbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ngbaxtbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:computer-chip-1-solid" /></template>
