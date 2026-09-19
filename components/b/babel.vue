<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfz452bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jfz452bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:babel" /></template>
