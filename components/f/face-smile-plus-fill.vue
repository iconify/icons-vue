<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf_wbmbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf_wbmbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-smile-plus-fill" /></template>
