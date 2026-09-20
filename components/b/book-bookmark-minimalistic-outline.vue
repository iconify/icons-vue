<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yheqtv8bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yheqtv8bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:book-bookmark-minimalistic-outline" /></template>
