<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avy81kbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avy81kbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:github-line" /></template>
