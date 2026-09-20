<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b16m7bc_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b16m7bc_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:apple-remix" /></template>
