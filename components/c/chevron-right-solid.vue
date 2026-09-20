<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywoke0pnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywoke0pnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-right-solid" /></template>
