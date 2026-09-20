<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9cp-0g3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9cp-0g3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-outline" /></template>
