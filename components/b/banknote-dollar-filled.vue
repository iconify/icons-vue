<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h34m3h0js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h34m3h0js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:banknote-dollar-filled" /></template>
