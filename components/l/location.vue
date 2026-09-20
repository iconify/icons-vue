<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty-lp-pnh.css';
import '../../css/m/mz_p1xb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty-lp-pnh"/><path clip-rule="evenodd" class="mz_p1xb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:location" /></template>
