<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n5flk5b-y.css';
import '../../css/i/i7zipxbti.css';
import '../../css/t/tpurk853y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n5flk5b-y"/><path class="i7zipxbti"/><path class="tpurk853y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-04" /></template>
