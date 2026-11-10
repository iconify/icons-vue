<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqa7h_o0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqa7h_o0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bookmark-check-solid" /></template>
