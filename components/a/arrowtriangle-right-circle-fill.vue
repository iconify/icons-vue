<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op10nbbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="op10nbbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-right-circle-fill" /></template>
