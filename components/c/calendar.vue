<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bptr-xbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bptr-xbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:calendar" /></template>
