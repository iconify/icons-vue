<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr-j5cbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr-j5cbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:knife-02" /></template>
