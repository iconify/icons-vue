<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho9c_64qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho9c_64qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-quick-outline" /></template>
