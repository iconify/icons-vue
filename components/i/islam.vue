<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veoe9mbus.css';
import '../../css/p/pf8dc_bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veoe9mbus"/><path class="pf8dc_bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:islam" /></template>
