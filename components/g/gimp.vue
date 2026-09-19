<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziaj1qlxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ziaj1qlxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gimp" /></template>
