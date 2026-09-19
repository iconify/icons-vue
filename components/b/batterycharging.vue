<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go4klvj4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="go4klvj4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:batterycharging" /></template>
