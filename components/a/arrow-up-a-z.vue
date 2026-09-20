<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kav1tbf9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kav1tbf9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-a-z" /></template>
