<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4eklxbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z4eklxbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:check-correct-filled" /></template>
