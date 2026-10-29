<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1vsz59_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1vsz59_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cat-solid" /></template>
