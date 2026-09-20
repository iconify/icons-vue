<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywdhsw-0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywdhsw-0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:file-bookmark-solid" /></template>
