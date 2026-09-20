<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo81odqdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo81odqdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home5" /></template>
