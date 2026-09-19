<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5fec3gku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5fec3gku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:bin" /></template>
