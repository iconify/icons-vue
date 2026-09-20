<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3m7n9bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z3m7n9bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:flickr" /></template>
