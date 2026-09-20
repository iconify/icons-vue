<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etofa9b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etofa9b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:check-duotone" /></template>
