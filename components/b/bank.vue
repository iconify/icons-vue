<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzk-r7a0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jzk-r7a0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:bank" /></template>
