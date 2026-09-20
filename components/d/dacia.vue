<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghzaz6bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghzaz6bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dacia" /></template>
