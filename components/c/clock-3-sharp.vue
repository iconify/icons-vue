<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz0oc4b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz0oc4b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-3-sharp" /></template>
