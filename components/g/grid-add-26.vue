<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8e9n1-iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="w8e9n1-iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-add-26" /></template>
