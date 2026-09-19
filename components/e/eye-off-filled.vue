<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skc1_tbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skc1_tbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:eye-off-filled" /></template>
