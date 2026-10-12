<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_c-psuak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_c-psuak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-down-from-line" /></template>
