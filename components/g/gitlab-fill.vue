<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqu-t3b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqu-t3b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gitlab-fill" /></template>
