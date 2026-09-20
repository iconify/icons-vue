<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-irwm9cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-irwm9cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-square-sharp" /></template>
