<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj4bs2b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="cj4bs2b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:books" /></template>
