<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wta-9zxow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wta-9zxow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:highlight" /></template>
