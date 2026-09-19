<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g88ua1b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g88ua1b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:doube-window-l-open" /></template>
