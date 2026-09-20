<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx2pjyjng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wx2pjyjng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-check-outline" /></template>
