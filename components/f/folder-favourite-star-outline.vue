<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckp9iqb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckp9iqb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-favourite-star-outline" /></template>
