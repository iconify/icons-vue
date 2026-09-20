<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiu4-0byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="yiu4-0byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:anchor-solid" /></template>
