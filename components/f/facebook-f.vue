<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emp192bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="emp192bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:facebook-f" /></template>
