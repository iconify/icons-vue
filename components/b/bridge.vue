<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy9y9-beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy9y9-beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bridge" /></template>
