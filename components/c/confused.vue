<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pus3fplgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pus3fplgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:confused" /></template>
