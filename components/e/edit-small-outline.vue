<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6rvq-b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a6rvq-b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:edit-small-outline" /></template>
