<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu9c9mm4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu9c9mm4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:category-plus" /></template>
