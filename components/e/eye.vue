<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpw-r42eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":740,"height":700};
const content = `<path class="hpw-r42eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:eye" /></template>
