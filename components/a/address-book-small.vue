<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/husm8abss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="husm8abss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:address-book-small" /></template>
