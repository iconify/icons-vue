<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm1p_cn4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vm1p_cn4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:iwiw-logo-2-block" /></template>
