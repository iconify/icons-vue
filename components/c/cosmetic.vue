<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psikjbcgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psikjbcgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cosmetic" /></template>
