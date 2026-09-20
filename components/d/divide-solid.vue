<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lflfbtdmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lflfbtdmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:divide-solid" /></template>
