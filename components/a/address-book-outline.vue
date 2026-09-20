<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_34kqjcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f_34kqjcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:address-book-outline" /></template>
