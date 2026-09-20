<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzkzy7e_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzkzy7e_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-1-solid" /></template>
