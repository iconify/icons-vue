<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hugsjk8ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hugsjk8ob primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ease-out-duotone" /></template>
