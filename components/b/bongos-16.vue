<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd9bq4beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jd9bq4beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bongos-16" /></template>
