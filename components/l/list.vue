<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apee3r9_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="apee3r9_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:list" /></template>
