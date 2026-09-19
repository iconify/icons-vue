<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhv6hlbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xhv6hlbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-plus-20-solid" /></template>
