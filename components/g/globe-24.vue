<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb3h_o76w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb3h_o76w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:globe-24" /></template>
