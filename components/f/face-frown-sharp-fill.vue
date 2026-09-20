<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsocbf_2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsocbf_2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-frown-sharp-fill" /></template>
