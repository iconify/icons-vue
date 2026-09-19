<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6v241bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c6v241bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-bin-fill" /></template>
