<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5cc2kldq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b5cc2kldq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:billboard" /></template>
