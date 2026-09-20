<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhsv77bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bhsv77bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:empire" /></template>
