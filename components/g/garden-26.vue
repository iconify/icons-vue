<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrgynsbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="qrgynsbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:garden-26" /></template>
