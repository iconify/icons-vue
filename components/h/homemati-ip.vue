<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnzkw5bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnzkw5bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:homemati-ip" /></template>
