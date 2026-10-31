<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_tdlddrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_tdlddrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-plus-round" /></template>
