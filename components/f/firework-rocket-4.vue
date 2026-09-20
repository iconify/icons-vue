<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvpgfle6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvpgfle6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:firework-rocket-4" /></template>
