<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iudvyabto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iudvyabto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ibeacon" /></template>
