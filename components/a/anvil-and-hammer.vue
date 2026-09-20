<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncl2nwb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ncl2nwb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:anvil-and-hammer" /></template>
