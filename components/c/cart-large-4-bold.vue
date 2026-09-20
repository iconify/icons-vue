<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2dq6fbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2dq6fbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-large-4-bold" /></template>
