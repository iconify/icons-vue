<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9hw7ehsm.css';
import '../../css/g/g9h7rdbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9hw7ehsm"/><path class="g9h7rdbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:link" /></template>
