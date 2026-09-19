<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh_2lkh4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xh_2lkh4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:infinity" /></template>
