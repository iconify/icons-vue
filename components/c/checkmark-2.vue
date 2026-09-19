<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u26dwrbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u26dwrbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-2" /></template>
