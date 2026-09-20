<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4i-ijb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4i-ijb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-sharp-fill" /></template>
