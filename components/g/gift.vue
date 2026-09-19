<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt6ytgt-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt6ytgt-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:gift" /></template>
