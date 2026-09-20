<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh5dbu6ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh5dbu6ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:cylinder" /></template>
