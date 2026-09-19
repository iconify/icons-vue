<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma5rg2bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1132,"height":626};
const content = `<path class="ma5rg2bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:heteml" /></template>
