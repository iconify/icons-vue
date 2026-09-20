<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmzvwc6ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rmzvwc6ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:madison-cross" /></template>
