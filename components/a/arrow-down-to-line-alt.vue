<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gloa1yb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gloa1yb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-to-line-alt" /></template>
