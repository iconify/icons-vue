<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fujt1ib7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="fujt1ib7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:inbox" /></template>
