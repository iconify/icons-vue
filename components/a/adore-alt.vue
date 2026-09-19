<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rehd27bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rehd27bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:adore-alt" /></template>
