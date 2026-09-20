<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipsj9zfzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ipsj9zfzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:layout-rtl" /></template>
