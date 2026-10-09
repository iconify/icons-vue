<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-jm55j8c.css';
import '../../css/j/j-o8fhbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k-jm55j8c"/><path class="j-o8fhbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ladle-20-bold" /></template>
