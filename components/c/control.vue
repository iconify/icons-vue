<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqk0ub_ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wqk0ub_ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:control" /></template>
