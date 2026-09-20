<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m49f24b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m49f24b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:adobe-alt" /></template>
