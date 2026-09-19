<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1g8j_m8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="a1g8j_m8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bolt-horizontal-circle" /></template>
