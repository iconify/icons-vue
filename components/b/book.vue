<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcf9s7b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bcf9s7b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:book" /></template>
