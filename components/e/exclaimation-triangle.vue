<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbamd212o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hbamd212o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:exclaimation-triangle" /></template>
