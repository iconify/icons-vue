<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5l4uj3dn.css';
import '../../css/q/q-lo6_bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="i5l4uj3dn"/><path class="q-lo6_bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hotel-alt" /></template>
