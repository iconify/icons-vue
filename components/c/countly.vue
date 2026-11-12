<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_487xz5h.css';
import '../../css/a/a-n77rjap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_487xz5h"/><path class="a-n77rjap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:countly" /></template>
