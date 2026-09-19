<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o97im9hdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":24};
const content = `<path class="o97im9hdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:facebook" /></template>
