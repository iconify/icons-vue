<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pasf08bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pasf08bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:harmonyos" /></template>
