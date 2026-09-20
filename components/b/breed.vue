<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq_dl8bqj.css';
import '../../css/a/asuar4emf.css';
import '../../css/f/f8sf7yhpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq_dl8bqj"/><path class="asuar4emf"/><path class="f8sf7yhpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:breed" /></template>
