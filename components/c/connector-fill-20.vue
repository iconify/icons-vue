<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l91gf31ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l91gf31ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:connector-fill-20" /></template>
