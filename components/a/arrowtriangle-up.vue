<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cju9lz9dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cju9lz9dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-up" /></template>
