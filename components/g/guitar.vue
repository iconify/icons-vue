<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoy4dks5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="eoy4dks5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:guitar" /></template>
