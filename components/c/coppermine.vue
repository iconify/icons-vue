<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7qmfwi7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="x7qmfwi7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:coppermine" /></template>
