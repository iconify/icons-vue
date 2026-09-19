<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz_v76b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cz_v76b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bookmark" /></template>
