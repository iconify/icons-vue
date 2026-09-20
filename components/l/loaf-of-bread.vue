<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq3zjyb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iq3zjyb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:loaf-of-bread" /></template>
