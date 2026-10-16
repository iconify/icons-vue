<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utjy8ob5b.css';
import '../../css/t/tzya4mwzm.css';
import '../../css/c/cofnes2hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="utjy8ob5b"/><path class="tzya4mwzm"/><path class="cofnes2hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lockout-20-bold" /></template>
