<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjtzypblm.css';
import '../../css/l/lg8uylb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjtzypblm"/><path class="lg8uylb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:charging-battery-medium-1-bold" /></template>
