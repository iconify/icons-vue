<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smg3t6jju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smg3t6jju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-up" /></template>
