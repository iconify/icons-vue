<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbxewab1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbxewab1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-number-8-filled" /></template>
