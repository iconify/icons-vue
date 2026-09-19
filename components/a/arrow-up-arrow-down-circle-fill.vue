<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbgiv_bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kbgiv_bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-arrow-down-circle-fill" /></template>
