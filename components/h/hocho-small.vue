<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkvofpbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qkvofpbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hocho-small" /></template>
