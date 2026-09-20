<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0zmwl6su.css';
import '../../css/d/d_zjijokg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0zmwl6su"/><path class="d_zjijokg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:file-xmark" /></template>
