<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v--_2jb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v--_2jb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cursor-rays" /></template>
