<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_v2c-7io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_v2c-7io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-books-dark" /></template>
