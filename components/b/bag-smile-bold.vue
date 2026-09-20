<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zst_8kb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zst_8kb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-smile-bold" /></template>
