<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0w1l3idh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0w1l3idh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-align-top-filled" /></template>
