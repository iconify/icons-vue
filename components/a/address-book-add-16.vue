<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_lwr5nhm.css';
import '../../css/f/flbxrybmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c_lwr5nhm"/><path class="flbxrybmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:address-book-add-16" /></template>
