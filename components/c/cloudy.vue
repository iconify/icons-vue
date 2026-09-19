<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmcl-smta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmcl-smta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:cloudy" /></template>
