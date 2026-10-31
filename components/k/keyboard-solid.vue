<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvzq53buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zvzq53buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:keyboard-solid" /></template>
