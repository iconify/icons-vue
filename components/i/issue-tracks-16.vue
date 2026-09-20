<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk5hyp-iw.css';
import '../../css/u/ua94ilb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mk5hyp-iw"/><path class="ua94ilb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-tracks-16" /></template>
