<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_l5jb__u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_l5jb__u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-filter-plus-fill" /></template>
