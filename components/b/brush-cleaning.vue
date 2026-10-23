<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp0io-2sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp0io-2sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:brush-cleaning" /></template>
