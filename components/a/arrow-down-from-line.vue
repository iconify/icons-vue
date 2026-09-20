<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhvug1obf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhvug1obf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-from-line" /></template>
