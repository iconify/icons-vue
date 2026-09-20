<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th6z7zbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th6z7zbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:face-man" /></template>
