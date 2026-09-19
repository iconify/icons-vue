<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hutf_8bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hutf_8bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-right-square-fill" /></template>
