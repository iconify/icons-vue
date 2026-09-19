<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4qbnkxxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s4qbnkxxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder-circle" /></template>
