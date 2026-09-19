<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-n83abfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b-n83abfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-code-fill" /></template>
