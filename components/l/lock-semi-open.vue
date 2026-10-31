<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ierfddc8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ierfddc8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lock-semi-open" /></template>
