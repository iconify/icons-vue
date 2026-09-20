<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcpwybcwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcpwybcwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bus-2-fill" /></template>
