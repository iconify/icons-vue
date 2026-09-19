<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9084iy4v.css';
import '../../css/w/w78rzcbvq.css';
import '../../css/k/kuk6t8bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v9084iy4v"/><path class="w78rzcbvq"/><path class="kuk6t8bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:account-book-twotone" /></template>
