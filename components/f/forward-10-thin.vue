<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjofz7oow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vjofz7oow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:forward-10-thin" /></template>
