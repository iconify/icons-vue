<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls0nprbji.css';
import '../../css/u/uo-66kwym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ls0nprbji"/><path clip-rule="evenodd" class="uo-66kwym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-sun" /></template>
