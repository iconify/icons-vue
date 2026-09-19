<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5ldl_bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5ldl_bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-c" /></template>
