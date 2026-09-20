<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0v2eqqog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0v2eqqog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mac-24" /></template>
