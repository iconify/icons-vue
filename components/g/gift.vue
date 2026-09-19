<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j672eccre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j672eccre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:gift" /></template>
