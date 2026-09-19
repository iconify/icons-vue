<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysi1mubbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysi1mubbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:coveralls" /></template>
