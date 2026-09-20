<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqylbgb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqylbgb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gowalla-logo-4-solid" /></template>
