<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdvsb9bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pdvsb9bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:clipboard-list" /></template>
