<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avd91y_7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avd91y_7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x2" /></template>
