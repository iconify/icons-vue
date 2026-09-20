<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twbisjnza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twbisjnza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:cent" /></template>
