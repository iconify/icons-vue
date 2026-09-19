<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlxe_2blb.css';
import '../../css/v/viv7oac8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlxe_2blb"/><path class="viv7oac8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:credit-card-insert" /></template>
