<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8zk9jbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v8zk9jbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:caret-left" /></template>
