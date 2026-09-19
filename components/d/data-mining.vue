<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_gr6ubgr.css';
import '../../css/g/g77xgdc7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_gr6ubgr"/><path class="g77xgdc7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:data-mining" /></template>
