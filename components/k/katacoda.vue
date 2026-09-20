<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfr02dbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfr02dbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:katacoda" /></template>
