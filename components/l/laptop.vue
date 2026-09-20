<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce99elbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce99elbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:laptop" /></template>
