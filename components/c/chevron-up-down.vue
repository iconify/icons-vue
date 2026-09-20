<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khjrhnv3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khjrhnv3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-down" /></template>
