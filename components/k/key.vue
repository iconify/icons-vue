<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv9scvpbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv9scvpbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:key" /></template>
