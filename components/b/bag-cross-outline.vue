<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfm8lbbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vfm8lbbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-cross-outline" /></template>
