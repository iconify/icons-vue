<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru5m9utxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ru5m9utxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:instagram-square" /></template>
