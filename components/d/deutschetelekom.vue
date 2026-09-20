<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3a5vnwfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3a5vnwfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:deutschetelekom" /></template>
