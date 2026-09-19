<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he0c_3b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="he0c_3b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:cake" /></template>
