<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlii6advc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlii6advc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:carrot" /></template>
