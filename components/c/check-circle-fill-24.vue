<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkdtg4bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkdtg4bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:check-circle-fill-24" /></template>
