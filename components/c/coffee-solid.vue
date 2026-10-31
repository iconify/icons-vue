<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaj6wfblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oaj6wfblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:coffee-solid" /></template>
