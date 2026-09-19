<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3gnn2bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b3gnn2bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:link" /></template>
