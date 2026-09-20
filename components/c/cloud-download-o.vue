<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-k3b0q2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b-k3b0q2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cloud-download-o" /></template>
