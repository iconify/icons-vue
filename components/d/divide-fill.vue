<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp_rec7fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp_rec7fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:divide-fill" /></template>
