<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5mkpud2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k5mkpud2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:book-dead-solid" /></template>
