<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qks8ej-gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qks8ej-gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:langchaincorporate" /></template>
