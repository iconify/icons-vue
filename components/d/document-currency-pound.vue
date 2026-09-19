<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn3mbpbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn3mbpbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-pound" /></template>
