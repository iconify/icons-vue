<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngyz1ybdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ngyz1ybdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dribbblealt" /></template>
