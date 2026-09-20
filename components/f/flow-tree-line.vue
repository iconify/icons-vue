<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlz3lbr5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlz3lbr5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flow-tree-line" /></template>
