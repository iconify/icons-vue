<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpg62mbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tpg62mbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:ellipsis" /></template>
