<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps80jobms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ps80jobms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:image" /></template>
