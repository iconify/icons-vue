<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5_tenb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="k5_tenb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:goforward-60" /></template>
