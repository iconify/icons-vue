<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7rhdcbxy.css';
import '../../css/v/ve9aog86g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7rhdcbxy"/><path class="ve9aog86g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-up-bold" /></template>
