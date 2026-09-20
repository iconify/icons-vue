<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd96dbb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd96dbb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:location-off-target" /></template>
