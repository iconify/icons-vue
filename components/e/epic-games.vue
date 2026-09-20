<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fowq36bhd.css';
import '../../css/u/un3nlpbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fowq36bhd"/><path class="un3nlpbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:epic-games" /></template>
