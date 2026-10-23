<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_l_i2b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_l_i2b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dice-2" /></template>
