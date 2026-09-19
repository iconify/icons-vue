<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm7p-ib3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="zm7p-ib3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:lines" /></template>
