<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3dwbbbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="z3dwbbbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-bolt" /></template>
