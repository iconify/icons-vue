<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu8ot3m7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu8ot3m7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-circle-bold" /></template>
