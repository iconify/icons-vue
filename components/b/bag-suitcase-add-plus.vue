<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9bxnstuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9bxnstuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bag-suitcase-add-plus" /></template>
