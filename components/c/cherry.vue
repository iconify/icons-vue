<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu_pbxbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu_pbxbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cherry" /></template>
