<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqur01bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":551,"height":634};
const content = `<path class="fqur01bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:dark" /></template>
