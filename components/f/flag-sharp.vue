<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qakgb95pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qakgb95pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-sharp" /></template>
