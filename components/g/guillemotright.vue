<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu3kytnrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":516,"height":614};
const content = `<path class="hu3kytnrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:guillemotright" /></template>
