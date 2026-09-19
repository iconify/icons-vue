<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjv5ijdmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tjv5ijdmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:basecamp" /></template>
