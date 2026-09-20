<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rex75jb-y.css';
import '../../css/c/cv_qrx7lo.css';
import '../../css/k/kn5t4v-6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rex75jb-y"/><path class="cv_qrx7lo"/><path class="kn5t4v-6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bitkub-chain" /></template>
