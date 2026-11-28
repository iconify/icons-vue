<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyjz8j-0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyjz8j-0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:contract-lock" /></template>
