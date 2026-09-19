<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3tthjk-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="x3tthjk-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cassettealt" /></template>
