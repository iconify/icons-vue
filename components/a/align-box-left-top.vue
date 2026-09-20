<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyo-u17ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyo-u17ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-left-top" /></template>
