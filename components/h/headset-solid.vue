<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/simk8wbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="simk8wbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:headset-solid" /></template>
