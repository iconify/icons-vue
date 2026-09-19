<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_jjt_bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_jjt_bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrows-repeat-count-outline" /></template>
