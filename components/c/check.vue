<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb0vhebiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb0vhebiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:check" /></template>
