<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghybnh57b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghybnh57b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-right" /></template>
