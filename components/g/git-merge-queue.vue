<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx-4ybcmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx-4ybcmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:git-merge-queue" /></template>
