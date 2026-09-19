<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otk7xqulb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="otk7xqulb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:d-and-d-beyond" /></template>
