<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se4exfb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="se4exfb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ban-sharp-fill" /></template>
