<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwcpc15ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fwcpc15ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:id-card-alt" /></template>
