<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5aptobji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5aptobji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:coffee" /></template>
