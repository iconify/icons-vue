<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci6zfr-zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci6zfr-zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copyright-fill" /></template>
