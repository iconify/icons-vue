<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxi0iukvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxi0iukvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:localsend" /></template>
