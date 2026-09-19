<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5jd9e2qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":512};
const content = `<path class="h5jd9e2qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:clothes-water" /></template>
