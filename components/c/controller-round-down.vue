<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb9wwdb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb9wwdb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-round-down" /></template>
