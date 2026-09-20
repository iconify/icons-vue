<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnbl065fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnbl065fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:light-switch-on" /></template>
