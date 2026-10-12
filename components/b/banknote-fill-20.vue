<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_p666_yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w_p666_yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:banknote-fill-20" /></template>
