<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8l5l3cxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="s8l5l3cxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lock" /></template>
