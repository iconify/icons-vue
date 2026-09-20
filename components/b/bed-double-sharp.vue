<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk7uxg33b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk7uxg33b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-double-sharp" /></template>
