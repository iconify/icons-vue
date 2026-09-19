<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iizqkmlih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iizqkmlih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:css3" /></template>
