<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4_4mjb9l.css';
import '../../css/u/u3-0qjcak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4_4mjb9l"/><path class="u3-0qjcak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:incoming-call-rounded-bold" /></template>
