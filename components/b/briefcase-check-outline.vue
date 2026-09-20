<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm8mx7q9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm8mx7q9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-check-outline" /></template>
