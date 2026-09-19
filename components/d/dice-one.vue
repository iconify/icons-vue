<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eps3jxbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="eps3jxbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dice-one" /></template>
