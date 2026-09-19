<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag91xjrra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ag91xjrra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:level-down-alt" /></template>
