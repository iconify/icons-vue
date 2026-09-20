<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqk9lqbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqk9lqbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:check-sharp" /></template>
