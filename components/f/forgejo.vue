<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9ma__bqh.css';
import '../../css/t/td4gnzb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f9ma__bqh"/><path class="td4gnzb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:forgejo" /></template>
