<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boh9b_bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="boh9b_bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:info-fill" /></template>
