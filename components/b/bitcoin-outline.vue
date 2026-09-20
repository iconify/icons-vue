<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8m-lundb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r8m-lundb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bitcoin-outline" /></template>
