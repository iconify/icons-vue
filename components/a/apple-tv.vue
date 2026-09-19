<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc-k9xb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc-k9xb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple-tv" /></template>
