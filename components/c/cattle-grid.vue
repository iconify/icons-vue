<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zij3g3brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zij3g3brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cattle-grid" /></template>
