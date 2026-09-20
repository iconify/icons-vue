<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj8dkmkmu.css';
import '../../css/m/mvmn2eb4z.css';
import '../../css/n/nvr0ynxmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xj8dkmkmu"/><path class="mvmn2eb4z"/><path class="nvr0ynxmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-calendar-dark" /></template>
