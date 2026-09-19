<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuhzw_-te.css';
import '../../css/g/gn7buhpvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":9,"height":16};
const content = `<path class="zuhzw_-te"/><path class="gn7buhpvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:arrowdown" /></template>
