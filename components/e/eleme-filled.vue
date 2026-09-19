<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciisitb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ciisitb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:eleme-filled" /></template>
