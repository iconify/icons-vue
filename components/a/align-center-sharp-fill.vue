<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3qmjbc_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3qmjbc_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-sharp-fill" /></template>
