<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfv_bibjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfv_bibjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bug-alt" /></template>
