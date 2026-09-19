<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_o-vlmlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j_o-vlmlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-down-to-square" /></template>
