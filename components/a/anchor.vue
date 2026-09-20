<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbtykub1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbtykub1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:anchor" /></template>
