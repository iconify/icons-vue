<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvx4y13re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qvx4y13re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-jcb" /></template>
