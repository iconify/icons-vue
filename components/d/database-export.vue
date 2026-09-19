<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfn9b2zds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xfn9b2zds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:database-export" /></template>
