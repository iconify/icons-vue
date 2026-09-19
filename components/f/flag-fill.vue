<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcgzgubwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qcgzgubwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:flag-fill" /></template>
