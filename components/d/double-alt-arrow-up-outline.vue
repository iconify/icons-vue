<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d23hnspwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d23hnspwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-up-outline" /></template>
