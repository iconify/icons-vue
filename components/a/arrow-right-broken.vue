<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfg6wabjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfg6wabjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-broken" /></template>
