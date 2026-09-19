<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_2s79bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q_2s79bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:envelope-fill" /></template>
