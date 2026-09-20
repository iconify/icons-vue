<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmgy5nbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmgy5nbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:github-alt" /></template>
