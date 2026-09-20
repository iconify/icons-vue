<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyjp2ln2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xyjp2ln2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coconut-palm-tree" /></template>
