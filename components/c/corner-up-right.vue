<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl-eebb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl-eebb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:corner-up-right" /></template>
