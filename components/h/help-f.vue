<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr_vn-bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="pr_vn-bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:help-f" /></template>
