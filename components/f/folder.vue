<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs__5j4lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cs__5j4lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder" /></template>
