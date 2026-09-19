<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_031fbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":488};
const content = `<path class="j_031fbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:cinch" /></template>
