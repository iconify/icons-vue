<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl9q4rsxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl9q4rsxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-solid" /></template>
