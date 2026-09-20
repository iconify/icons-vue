<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8w5lx5ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8w5lx5ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-up" /></template>
