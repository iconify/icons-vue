<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq_o23b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kq_o23b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:heroku" /></template>
