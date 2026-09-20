<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bal_--nnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bal_--nnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gift-fill" /></template>
