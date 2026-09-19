<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-7oihfec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="o-7oihfec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:currency-pound" /></template>
