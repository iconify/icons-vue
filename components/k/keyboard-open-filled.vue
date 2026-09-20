<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t885h7bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t885h7bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:keyboard-open-filled" /></template>
