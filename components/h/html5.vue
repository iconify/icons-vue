<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbjmc1hvx.css';
import '../../css/m/mu4g-lbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbjmc1hvx"/><path clip-rule="evenodd" class="mu4g-lbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:html5" /></template>
