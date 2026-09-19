<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au_8zbb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="au_8zbb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-rain-fill" /></template>
