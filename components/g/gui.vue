<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t382k66tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t382k66tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gui" /></template>
