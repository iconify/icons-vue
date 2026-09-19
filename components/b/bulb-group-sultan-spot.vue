<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwbei4b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwbei4b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-sultan-spot" /></template>
