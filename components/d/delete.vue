<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in6m0ccyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in6m0ccyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:delete" /></template>
