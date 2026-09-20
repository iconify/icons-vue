<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzu3tqzwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lzu3tqzwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:fork-16" /></template>
