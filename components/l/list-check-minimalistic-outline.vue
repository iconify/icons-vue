<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acm-y3bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acm-y3bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-check-minimalistic-outline" /></template>
