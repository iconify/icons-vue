<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0kbkz6ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x0kbkz6ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lungs" /></template>
