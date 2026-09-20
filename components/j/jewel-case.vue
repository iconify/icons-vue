<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1yd4q-nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1yd4q-nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:jewel-case" /></template>
