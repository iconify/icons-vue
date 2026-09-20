<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzby4kz3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzby4kz3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:dropbox" /></template>
