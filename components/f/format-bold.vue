<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_31fsyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca_31fsyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-bold" /></template>
