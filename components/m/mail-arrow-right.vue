<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvdgx_4vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvdgx_4vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mail-arrow-right" /></template>
