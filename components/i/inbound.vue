<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/votb_pbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="votb_pbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:inbound" /></template>
