<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9htj8btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9htj8btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ens" /></template>
