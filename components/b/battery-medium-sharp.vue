<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvu-1h28a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvu-1h28a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-medium-sharp" /></template>
