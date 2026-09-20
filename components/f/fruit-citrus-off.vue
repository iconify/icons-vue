<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ine0nfmfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ine0nfmfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fruit-citrus-off" /></template>
