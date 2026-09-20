<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz763296q.css';
import '../../css/k/kgp-egvzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz763296q"/><path class="kgp-egvzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:espiral-book" /></template>
