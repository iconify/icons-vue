<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6r3qwg2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":9};
const content = `<path class="f6r3qwg2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:caretdown" /></template>
