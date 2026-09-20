<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giiqp_bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giiqp_bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag" /></template>
