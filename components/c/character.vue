<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za2ck5ubr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="za2ck5ubr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:character" /></template>
