<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz4xc3lnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz4xc3lnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hammer" /></template>
