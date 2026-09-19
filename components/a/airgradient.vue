<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w075n_c4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w075n_c4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:airgradient" /></template>
