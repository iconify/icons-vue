<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkxsjvhwz.css';
import '../../css/j/jzj453buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pkxsjvhwz"/><path clip-rule="evenodd" class="jzj453buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:address-book-16" /></template>
