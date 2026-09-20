<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krths5bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krths5bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:at-solid" /></template>
