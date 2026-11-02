<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypqpinbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypqpinbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-line" /></template>
