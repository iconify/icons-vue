<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_gup7b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="o_gup7b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:attraction-11" /></template>
