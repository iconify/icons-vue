<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbuj5abca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbuj5abca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-top-left-broken" /></template>
