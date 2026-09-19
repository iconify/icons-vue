<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0giy58mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c0giy58mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lock-slash-fill" /></template>
