<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpunj9qsv.css';
import '../../css/d/dzeier91r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vpunj9qsv"/><path clip-rule="evenodd" class="dzeier91r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:book-solid" /></template>
