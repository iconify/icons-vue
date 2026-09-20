<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twh9358jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="twh9358jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-2-solid" /></template>
