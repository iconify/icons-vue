<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nclo1ib8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nclo1ib8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bug-report" /></template>
