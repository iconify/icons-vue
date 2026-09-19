<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3az_8srk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":547,"height":762};
const content = `<path class="x3az_8srk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:a-upper-case" /></template>
