<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6kkc4bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6kkc4bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:commit-outlined" /></template>
