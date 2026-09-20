<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehihvu1_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehihvu1_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-right-sharp-duotone" /></template>
