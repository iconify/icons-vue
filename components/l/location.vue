<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oysno6b8h.css';
import '../../css/i/ijdqjaczl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="oysno6b8h"/><path class="ijdqjaczl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:location" /></template>
