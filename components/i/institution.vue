<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlcu1mk_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="nlcu1mk_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:institution" /></template>
