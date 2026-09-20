<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip1i70bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip1i70bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ariakit" /></template>
