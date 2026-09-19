<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s37qc_bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s37qc_bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:bag-outline" /></template>
