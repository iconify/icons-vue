<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfxo03bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfxo03bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chevron-compact-right" /></template>
