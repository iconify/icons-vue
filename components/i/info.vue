<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa3v6eogt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa3v6eogt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:info" /></template>
