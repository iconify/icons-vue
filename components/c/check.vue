<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ojfcb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ojfcb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:check" /></template>
