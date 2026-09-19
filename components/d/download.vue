<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9k8jmgpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h9k8jmgpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:download" /></template>
