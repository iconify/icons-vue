<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv_--b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkv_--b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-plus-solid" /></template>
