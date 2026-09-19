<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f23z082ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f23z082ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kuma" /></template>
