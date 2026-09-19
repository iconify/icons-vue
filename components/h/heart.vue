<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4-zwccpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="b4-zwccpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:heart" /></template>
