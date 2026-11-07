<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdep0-bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdep0-bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-broken" /></template>
