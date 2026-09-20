<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scifenb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scifenb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chevron-left-line" /></template>
