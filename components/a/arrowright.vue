<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmntw8r6r.css';
import '../../css/l/lc5m63-4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":9};
const content = `<path class="nmntw8r6r"/><path class="lc5m63-4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:arrowright" /></template>
