<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq4ep8a-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq4ep8a-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-cancel" /></template>
