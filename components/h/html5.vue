<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahw-91_je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="ahw-91_je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:html5" /></template>
