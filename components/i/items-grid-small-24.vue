<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va8rt5bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="va8rt5bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:items-grid-small-24" /></template>
