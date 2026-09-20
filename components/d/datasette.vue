<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c66xcebar.css';
import '../../css/a/at6xz-pmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c66xcebar"/><path class="at6xz-pmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:datasette" /></template>
