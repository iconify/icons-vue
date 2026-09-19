<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a33d7c0oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a33d7c0oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:fingerprint-outline" /></template>
