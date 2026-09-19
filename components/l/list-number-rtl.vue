<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejuhadc8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ejuhadc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:list-number-rtl" /></template>
