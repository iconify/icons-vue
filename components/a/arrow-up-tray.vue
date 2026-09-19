<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otved71qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otved71qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-tray" /></template>
