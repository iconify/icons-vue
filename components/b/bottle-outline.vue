<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccnh3bckv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ccnh3bckv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bottle-outline" /></template>
