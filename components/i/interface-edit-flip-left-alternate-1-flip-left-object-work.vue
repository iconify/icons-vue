<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgel_fcqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bgel_fcqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-flip-left-alternate-1-flip-left-object-work" /></template>
