<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fscgq4lir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fscgq4lir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:castle-with-spires" /></template>
