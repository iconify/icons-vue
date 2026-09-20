<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts_urt4hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts_urt4hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:google" /></template>
