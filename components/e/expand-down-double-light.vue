<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn45-2bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn45-2bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-down-double-light" /></template>
