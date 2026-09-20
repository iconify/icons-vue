<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4uy-0bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="t4uy-0bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-plus-solid" /></template>
