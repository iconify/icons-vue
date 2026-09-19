<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltj9geb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ltj9geb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:list-number" /></template>
