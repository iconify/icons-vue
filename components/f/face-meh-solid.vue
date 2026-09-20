<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnj9e-bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dnj9e-bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-meh-solid" /></template>
