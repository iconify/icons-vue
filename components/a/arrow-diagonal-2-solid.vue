<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6-5sk_bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w6-5sk_bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-diagonal-2-solid" /></template>
