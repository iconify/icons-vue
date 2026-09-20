<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lklontbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lklontbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:macaron-16" /></template>
