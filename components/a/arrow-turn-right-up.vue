<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfdi55bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jfdi55bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-turn-right-up" /></template>
