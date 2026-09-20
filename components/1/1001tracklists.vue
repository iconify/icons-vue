<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x943lnvxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x943lnvxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:1001tracklists" /></template>
