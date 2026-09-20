<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsf80cbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsf80cbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-2-outline" /></template>
