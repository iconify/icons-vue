<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj-udt_6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":655,"height":674};
const content = `<path class="mj-udt_6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:delicious" /></template>
