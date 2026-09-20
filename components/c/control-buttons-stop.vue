<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bia8e8idd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bia8e8idd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-stop" /></template>
