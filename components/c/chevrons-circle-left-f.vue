<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc5jrr1xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="pc5jrr1xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-circle-left-f" /></template>
