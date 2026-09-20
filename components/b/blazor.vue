<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvbs_bbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvbs_bbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:blazor" /></template>
