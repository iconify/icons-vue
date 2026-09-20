<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plhb_68gt.css';
import '../../css/x/xwzdy07rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="plhb_68gt"/><path class="xwzdy07rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:external-link" /></template>
