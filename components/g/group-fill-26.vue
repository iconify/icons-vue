<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqgn4v-kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="gqgn4v-kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:group-fill-26" /></template>
