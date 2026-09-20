<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iemrbslri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iemrbslri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-1-sharp" /></template>
