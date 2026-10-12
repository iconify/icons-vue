<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvt-fvj0a.css';
import '../../css/h/hxwzeibnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pvt-fvj0a"/><path class="hxwzeibnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:basket-plus-stroke-20" /></template>
