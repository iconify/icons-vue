<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_c43pbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s_c43pbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:flag-circle-fill" /></template>
