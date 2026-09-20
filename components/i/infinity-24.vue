<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_8bf5a3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_8bf5a3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:infinity-24" /></template>
