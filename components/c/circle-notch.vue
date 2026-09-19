<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_0bcc28t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t_0bcc28t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:circle-notch" /></template>
