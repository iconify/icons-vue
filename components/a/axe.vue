<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bina6-boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bina6-boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axe" /></template>
