<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdzfnr7gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdzfnr7gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:google-outline" /></template>
