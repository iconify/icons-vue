<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ako15q_2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ako15q_2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-up-left" /></template>
