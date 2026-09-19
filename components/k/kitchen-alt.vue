<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lva73_tux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lva73_tux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kitchen-alt" /></template>
