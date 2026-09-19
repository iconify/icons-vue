<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgtm16bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgtm16bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-right" /></template>
