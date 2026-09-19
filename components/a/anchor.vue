<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la-n7dbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="la-n7dbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:anchor" /></template>
