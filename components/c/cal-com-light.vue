<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp2fzbc_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wp2fzbc_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cal-com-light" /></template>
