<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kna5n_8so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kna5n_8so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-down-solid" /></template>
