<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spf_7nb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="spf_7nb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:hardware-printer" /></template>
