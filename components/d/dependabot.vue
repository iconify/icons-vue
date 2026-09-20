<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w809qnbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w809qnbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dependabot" /></template>
