<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj2dn_dhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj2dn_dhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:find-love" /></template>
