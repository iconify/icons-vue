<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5t9f007a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5t9f007a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-export-filled" /></template>
