<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea74grkel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea74grkel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:biohazard-fill-round" /></template>
