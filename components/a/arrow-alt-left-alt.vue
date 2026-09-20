<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm1j5hbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm1j5hbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-alt-left-alt" /></template>
