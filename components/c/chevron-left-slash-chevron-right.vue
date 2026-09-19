<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndywibi8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ndywibi8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-left-slash-chevron-right" /></template>
