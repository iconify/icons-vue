<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1pz90bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="c1pz90bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:dentist-11" /></template>
