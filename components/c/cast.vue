<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plsckdbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plsckdbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cast" /></template>
