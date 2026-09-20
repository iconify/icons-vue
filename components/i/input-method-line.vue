<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aph27i7aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aph27i7aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:input-method-line" /></template>
