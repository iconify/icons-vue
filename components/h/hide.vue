<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpqrq41mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpqrq41mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:hide" /></template>
