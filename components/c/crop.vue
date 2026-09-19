<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqgc92ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="kjqgc92ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:crop" /></template>
