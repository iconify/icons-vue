<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuw5yubgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuw5yubgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brain-cog-sharp" /></template>
