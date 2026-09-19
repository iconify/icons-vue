<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4d1k9bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4d1k9bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arlo-baby" /></template>
