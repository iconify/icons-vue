<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgwizui3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="dgwizui3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:center-align" /></template>
