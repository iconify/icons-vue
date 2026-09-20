<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvn4_zbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rvn4_zbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray-and-yen-yuan" /></template>
