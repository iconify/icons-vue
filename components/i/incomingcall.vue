<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvysm6ifx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="lvysm6ifx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:incomingcall" /></template>
