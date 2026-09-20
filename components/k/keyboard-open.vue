<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr_7g48pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr_7g48pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:keyboard-open" /></template>
