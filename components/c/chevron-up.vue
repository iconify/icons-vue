<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnyejdb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xnyejdb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-up" /></template>
