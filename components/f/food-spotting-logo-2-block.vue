<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks5i7cc0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks5i7cc0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:food-spotting-logo-2-block" /></template>
