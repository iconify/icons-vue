<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0_zj3bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="l0_zj3bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:cut" /></template>
