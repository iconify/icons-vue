<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2vxofbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o2vxofbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:bag" /></template>
