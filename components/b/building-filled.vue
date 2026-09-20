<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iojvz4bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iojvz4bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:building-filled" /></template>
