<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snp3cqm3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snp3cqm3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bike-solid" /></template>
