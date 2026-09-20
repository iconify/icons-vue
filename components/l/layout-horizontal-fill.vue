<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imbkg0n5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imbkg0n5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-horizontal-fill" /></template>
