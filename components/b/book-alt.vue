<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erqsdj16a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="erqsdj16a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:book-alt" /></template>
