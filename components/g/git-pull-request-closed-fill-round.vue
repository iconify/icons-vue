<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi6mprboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi6mprboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-pull-request-closed-fill-round" /></template>
