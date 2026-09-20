<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn0pp-bpg.css';
import '../../css/v/v3kgvknic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn0pp-bpg"/><path class="v3kgvknic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fast-forward-line" /></template>
