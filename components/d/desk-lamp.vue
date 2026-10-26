<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hanaa5bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hanaa5bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desk-lamp" /></template>
