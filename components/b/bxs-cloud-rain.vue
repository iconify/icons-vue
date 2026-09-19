<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk7827bhk.css';
import '../../css/d/dkh-5rbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk7827bhk"/><path class="dkh-5rbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cloud-rain" /></template>
