<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pek76-bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pek76-bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:home-filled" /></template>
