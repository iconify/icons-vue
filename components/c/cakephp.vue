<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzwjxbbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vzwjxbbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cakephp" /></template>
