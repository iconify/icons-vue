<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sifkdq4hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sifkdq4hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:camera-fill" /></template>
