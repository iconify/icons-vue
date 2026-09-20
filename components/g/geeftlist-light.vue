<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7f8ufmsj.css';
import '../../css/a/abjuxlr8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7f8ufmsj"/><path class="abjuxlr8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:geeftlist-light" /></template>
