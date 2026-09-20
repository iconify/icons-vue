<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb6gv4imc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb6gv4imc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:form-validation-cursor-choose" /></template>
