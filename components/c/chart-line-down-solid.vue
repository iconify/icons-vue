<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_tky7bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_tky7bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chart-line-down-solid" /></template>
