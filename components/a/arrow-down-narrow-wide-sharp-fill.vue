<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vscd-0bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vscd-0bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-narrow-wide-sharp-fill" /></template>
