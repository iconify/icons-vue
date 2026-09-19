<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fss3asbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="fss3asbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:iron-any-temp" /></template>
