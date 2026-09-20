<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8q0sd-0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8q0sd-0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-less-duotone" /></template>
