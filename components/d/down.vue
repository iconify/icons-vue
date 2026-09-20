<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6d-ncbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n6d-ncbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:down" /></template>
