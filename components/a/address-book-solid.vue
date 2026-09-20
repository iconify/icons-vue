<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztsas3gev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ztsas3gev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:address-book-solid" /></template>
