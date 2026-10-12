<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqgrzwrtu.css';
import '../../css/j/jahmehbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eqgrzwrtu"/><path class="jahmehbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-box-down-20" /></template>
