<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2nz4slzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2nz4slzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:close-policy-gaps-alt-outline-24px" /></template>
