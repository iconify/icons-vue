<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-mbilwso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o-mbilwso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chevrons-right" /></template>
