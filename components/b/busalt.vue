<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mms97ybfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":696};
const content = `<path class="mms97ybfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:busalt" /></template>
