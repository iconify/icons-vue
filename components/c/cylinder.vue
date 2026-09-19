<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oke1umbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oke1umbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:cylinder" /></template>
