<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea1gftbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea1gftbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:eclipseche" /></template>
