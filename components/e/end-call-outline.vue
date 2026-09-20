<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3b9dkb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3b9dkb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-outline" /></template>
