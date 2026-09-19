<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-3m8fbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b-3m8fbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-minus-fill" /></template>
