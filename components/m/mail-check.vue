<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbox0sb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbox0sb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-check" /></template>
