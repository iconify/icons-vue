<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2tqi_tyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2tqi_tyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ginetex:any-bleach-allowed" /></template>
