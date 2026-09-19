<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-2zj3b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-2zj3b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flag-02" /></template>
