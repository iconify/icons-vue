<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz2dn1bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz2dn1bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:forest" /></template>
