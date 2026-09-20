<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyawl_bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gyawl_bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:blood-cells" /></template>
