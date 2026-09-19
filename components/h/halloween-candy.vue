<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs5zptt1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs5zptt1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-candy" /></template>
