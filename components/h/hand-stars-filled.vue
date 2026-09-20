<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g119dzb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g119dzb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-stars-filled" /></template>
