<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8rxfu3fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8rxfu3fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:chevron-left-circle" /></template>
