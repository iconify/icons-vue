<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqrpx5agk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqrpx5agk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-u-turn-right-solid" /></template>
