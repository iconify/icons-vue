<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8gd2ib8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8gd2ib8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:donut-outline" /></template>
