<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcw80rb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcw80rb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x3-solid" /></template>
