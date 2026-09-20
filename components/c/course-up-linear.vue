<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy27c67ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy27c67ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:course-up-linear" /></template>
