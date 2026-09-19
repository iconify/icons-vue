<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqgw_vb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oqgw_vb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlex" /></template>
