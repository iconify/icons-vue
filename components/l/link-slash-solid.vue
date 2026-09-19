<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rck100efq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rck100efq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:link-slash-solid" /></template>
