<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrl5tih3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrl5tih3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:insomnia" /></template>
