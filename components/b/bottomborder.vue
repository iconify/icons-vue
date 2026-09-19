<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df4b_9t3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="df4b_9t3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bottomborder" /></template>
