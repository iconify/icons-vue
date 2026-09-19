<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxirfpbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxirfpbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:check-solid" /></template>
