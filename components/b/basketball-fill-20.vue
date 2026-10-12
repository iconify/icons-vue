<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah4goccvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ah4goccvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:basketball-fill-20" /></template>
