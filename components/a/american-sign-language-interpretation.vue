<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyv-v7btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kyv-v7btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:american-sign-language-interpretation" /></template>
