<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfcb48v_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qfcb48v_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:image-portrait" /></template>
