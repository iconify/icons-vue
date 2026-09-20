<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x98thzm6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x98thzm6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:etesync-light" /></template>
