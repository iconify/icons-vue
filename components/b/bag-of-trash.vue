<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p29xtbdsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p29xtbdsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bag-of-trash" /></template>
