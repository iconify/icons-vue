<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2adkx72x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2adkx72x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:feather" /></template>
