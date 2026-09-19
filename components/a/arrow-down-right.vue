<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx63t23tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx63t23tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:arrow-down-right" /></template>
