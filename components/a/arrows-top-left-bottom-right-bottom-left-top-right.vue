<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9znblbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x9znblbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrows-top-left-bottom-right-bottom-left-top-right" /></template>
