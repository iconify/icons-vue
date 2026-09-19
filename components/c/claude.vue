<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijfone47c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ijfone47c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:claude" /></template>
