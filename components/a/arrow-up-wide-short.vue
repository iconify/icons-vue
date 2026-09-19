<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_2qg0fkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="j_2qg0fkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up-wide-short" /></template>
