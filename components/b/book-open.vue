<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssmc3qbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ssmc3qbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:book-open" /></template>
