<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnl6k-emx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bnl6k-emx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:drink-cup-with-straw-and-boba" /></template>
