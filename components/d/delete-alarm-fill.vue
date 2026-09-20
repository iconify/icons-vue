<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc7as45mv.css';
import '../../css/n/nsrryibqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc7as45mv"/><path clip-rule="evenodd" class="nsrryibqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:delete-alarm-fill" /></template>
