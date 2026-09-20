<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3-9yacyq.css';
import '../../css/p/p796kerln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="i3-9yacyq"/><path class="p796kerln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:american-eagle" /></template>
