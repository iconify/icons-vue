<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi1xs8bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi1xs8bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:flower" /></template>
