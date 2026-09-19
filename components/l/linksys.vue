<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-6rz8hpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-6rz8hpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:linksys" /></template>
