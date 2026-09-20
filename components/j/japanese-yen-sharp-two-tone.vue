<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1tym-4tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1tym-4tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:japanese-yen-sharp-two-tone" /></template>
