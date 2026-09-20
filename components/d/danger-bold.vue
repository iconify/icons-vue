<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfvb44b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfvb44b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-bold" /></template>
