<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy3ilwg6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy3ilwg6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:cync" /></template>
