<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhua4zb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uhua4zb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:left-filled" /></template>
