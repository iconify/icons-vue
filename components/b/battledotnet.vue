<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nar1_xb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nar1_xb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:battledotnet" /></template>
