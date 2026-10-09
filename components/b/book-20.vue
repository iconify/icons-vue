<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udfsdub4u.css';
import '../../css/j/j18dvotij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="udfsdub4u"/><path class="j18dvotij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:book-20" /></template>
