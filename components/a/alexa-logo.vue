<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whr5vg88n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whr5vg88n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:alexa-logo" /></template>
