<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2thbjb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2thbjb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:edit-2" /></template>
