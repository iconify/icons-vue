<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv3re6wbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv3re6wbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:google-home-icon" /></template>
