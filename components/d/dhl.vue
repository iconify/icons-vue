<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao_b-wo7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao_b-wo7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dhl" /></template>
