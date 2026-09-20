<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdg6dzb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rdg6dzb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:erg" /></template>
