<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo9szuzgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vo9szuzgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hauk-light" /></template>
