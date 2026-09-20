<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icp5hibgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="icp5hibgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-text" /></template>
