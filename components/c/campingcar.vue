<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwk_1c3ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lwk_1c3ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:campingcar" /></template>
